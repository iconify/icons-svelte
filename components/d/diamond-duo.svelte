<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs0n83b1m.css';
import '../../css/b/bats-ew3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs0n83b1m secondary"/><path class="bats-ew3c primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-duo" {...props}></Icon>
