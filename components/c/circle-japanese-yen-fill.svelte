<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvevhob7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvevhob7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-japanese-yen-fill" {...props}></Icon>
