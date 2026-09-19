<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ennyb0i.css';
import '../../css/n/n5rw468eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ennyb0i"/><path class="n5rw468eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-left-square" {...props}></Icon>
