<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvs6eib7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvs6eib7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cocos" {...props}></Icon>
