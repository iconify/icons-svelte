<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7mgf5qqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7mgf5qqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-2-outline" {...props}></Icon>
