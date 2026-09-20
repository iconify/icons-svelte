<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nylab0bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nylab0bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:androidauto" {...props}></Icon>
