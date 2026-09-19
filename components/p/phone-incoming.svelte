<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v42ex0_-k.css';
import '../../css/z/z0ygq5b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v42ex0_-k"/><path class="z0ygq5b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-incoming" {...props}></Icon>
