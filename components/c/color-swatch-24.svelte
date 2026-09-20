<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v34uau0cs.css';
import '../../css/o/oo8g7lyei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v34uau0cs"/><path clip-rule="evenodd" class="oo8g7lyei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:color-swatch-24" {...props}></Icon>
