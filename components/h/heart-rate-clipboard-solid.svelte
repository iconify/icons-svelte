<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr4bq0a-c.css';
import '../../css/k/kb19e1bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4bq0a-c"/><path clip-rule="evenodd" class="kb19e1bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:heart-rate-clipboard-solid" {...props}></Icon>
