<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8hmzvet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_8hmzvet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:books-2" {...props}></Icon>
