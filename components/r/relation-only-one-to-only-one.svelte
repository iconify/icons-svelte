<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5-sr2nuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5-sr2nuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-only-one-to-only-one" {...props}></Icon>
