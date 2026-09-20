<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7idm8bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7idm8bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forbidden-circle-outline" {...props}></Icon>
