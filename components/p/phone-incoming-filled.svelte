<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abv-ihbwo.css';
import '../../css/z/z0ygq5b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abv-ihbwo"/><path class="z0ygq5b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-incoming-filled" {...props}></Icon>
