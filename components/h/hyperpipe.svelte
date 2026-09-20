<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knv9mypjn.css';
import '../../css/o/oao8y4zzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knv9mypjn"/><path class="oao8y4zzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperpipe" {...props}></Icon>
