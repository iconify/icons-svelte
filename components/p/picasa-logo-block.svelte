<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i79c3zjsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i79c3zjsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:picasa-logo-block" {...props}></Icon>
