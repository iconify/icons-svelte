<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq3n7ab0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq3n7ab0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:hackernoon-purcat" {...props}></Icon>
