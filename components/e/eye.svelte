<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2k121bbm.css';
import '../../css/v/v-w2i5hqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2k121bbm"/><path class="v-w2i5hqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye" {...props}></Icon>
