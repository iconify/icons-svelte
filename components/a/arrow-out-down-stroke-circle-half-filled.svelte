<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijupqacst.css';
import '../../css/w/waapkib7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijupqacst"/><path class="waapkib7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-stroke-circle-half-filled" {...props}></Icon>
