<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqeyqsb0i.css';
import '../../css/d/dek9bkq9j.css';
import '../../css/s/svjtfbbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqeyqsb0i"/><path class="dek9bkq9j"/><path clip-rule="evenodd" class="svjtfbbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:passport-bold" {...props}></Icon>
