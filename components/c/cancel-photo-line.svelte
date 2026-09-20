<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk3ve9yfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk3ve9yfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:cancel-photo-line" {...props}></Icon>
