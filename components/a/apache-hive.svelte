<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs1-8nbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs1-8nbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-hive" {...props}></Icon>
