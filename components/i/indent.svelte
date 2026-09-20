<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_shecbdt.css';
import '../../css/w/wodq73bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="n_shecbdt"/><path clip-rule="evenodd" class="wodq73bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:indent" {...props}></Icon>
