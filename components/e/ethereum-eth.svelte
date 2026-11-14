<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o15086bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o15086bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ethereum-eth" {...props}></Icon>
