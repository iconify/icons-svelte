<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzh9j_86w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh9j_86w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:heart-fill" {...props}></Icon>
