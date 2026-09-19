<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxnslnd9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxnslnd9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-breake-h" {...props}></Icon>
