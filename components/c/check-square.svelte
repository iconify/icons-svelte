<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cidnmrdbv.css';
import '../../css/n/neifvedcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cidnmrdbv"/><path class="neifvedcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:check-square" {...props}></Icon>
