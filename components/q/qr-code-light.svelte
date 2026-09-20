<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab4vndb4j.css';
import '../../css/w/w_b7fnbhh.css';
import '../../css/c/c4ksf17xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab4vndb4j"/><path clip-rule="evenodd" class="w_b7fnbhh"/><path class="c4ksf17xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:qr-code-light" {...props}></Icon>
