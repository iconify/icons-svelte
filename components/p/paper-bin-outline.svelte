<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s64hfearz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s64hfearz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paper-bin-outline" {...props}></Icon>
