<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-i1pqbhz.css';
import '../../css/e/ecv-qkvdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-i1pqbhz"/><path class="ecv-qkvdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog-alt" {...props}></Icon>
