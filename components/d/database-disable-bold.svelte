<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8eigqm8a.css';
import '../../css/c/ccy8wxb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8eigqm8a"/><path class="ccy8wxb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:database-disable-bold" {...props}></Icon>
