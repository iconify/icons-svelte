<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smbnb7bef.css';
import '../../css/p/pln5qlbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smbnb7bef"/><path class="pln5qlbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:check-circle" {...props}></Icon>
