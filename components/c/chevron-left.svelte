<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpq8ief7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpq8ief7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:chevron-left" {...props}></Icon>
