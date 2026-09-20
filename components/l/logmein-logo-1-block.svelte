<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7vh48fqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k7vh48fqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:logmein-logo-1-block" {...props}></Icon>
