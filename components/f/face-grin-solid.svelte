<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlrhk_-_t.css';
import '../../css/b/blghhjben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlrhk_-_t"/><path class="blghhjben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-grin-solid" {...props}></Icon>
