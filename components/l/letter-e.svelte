<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9rxwc--v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9rxwc--v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-e" {...props}></Icon>
