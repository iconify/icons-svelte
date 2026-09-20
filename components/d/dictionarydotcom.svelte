<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxz3bzbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxz3bzbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dictionarydotcom" {...props}></Icon>
