<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym_r_5nav.css';
import '../../css/o/o7sf9lkhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym_r_5nav"/><path class="o7sf9lkhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:android-solid" {...props}></Icon>
