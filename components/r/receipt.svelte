<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gumdym6bg.css';
import '../../css/u/utf3i9a_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gumdym6bg"/><path class="utf3i9a_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:receipt" {...props}></Icon>
