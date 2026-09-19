<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqoi1y9qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqoi1y9qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:abstract-outlined" {...props}></Icon>
