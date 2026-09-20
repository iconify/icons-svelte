<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evmxdbcjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="evmxdbcjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accessibility-bold" {...props}></Icon>
