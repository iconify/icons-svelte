<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbu6hwbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbu6hwbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:outdent-solid" {...props}></Icon>
