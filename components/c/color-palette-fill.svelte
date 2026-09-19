<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwv3yflix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwv3yflix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:color-palette-fill" {...props}></Icon>
