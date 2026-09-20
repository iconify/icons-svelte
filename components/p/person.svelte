<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfmg-5_6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wfmg-5_6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:person" {...props}></Icon>
