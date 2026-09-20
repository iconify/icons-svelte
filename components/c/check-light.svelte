<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvw6idboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvw6idboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:check-light" {...props}></Icon>
