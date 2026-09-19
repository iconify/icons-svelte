<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l407iv7wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l407iv7wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-down-thick" {...props}></Icon>
