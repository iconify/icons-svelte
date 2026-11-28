<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk8fwjbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk8fwjbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chef-hat-star" {...props}></Icon>
