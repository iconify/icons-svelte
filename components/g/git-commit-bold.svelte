<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2cda_lwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2cda_lwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-commit-bold" {...props}></Icon>
