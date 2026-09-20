<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bozhqyb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bozhqyb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:hbo-max-logo-solid" {...props}></Icon>
