<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_3kybcfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_3kybcfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-2-block" {...props}></Icon>
