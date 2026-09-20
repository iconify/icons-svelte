<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz_2qjfda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz_2qjfda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:codeowners" {...props}></Icon>
