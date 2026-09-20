<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfr2iof0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfr2iof0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pinwheel" {...props}></Icon>
