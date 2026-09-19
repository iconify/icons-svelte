<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgky8kb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgky8kb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:male-02" {...props}></Icon>
