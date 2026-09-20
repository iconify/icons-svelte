<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm23l6zsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm23l6zsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apache-superset" {...props}></Icon>
