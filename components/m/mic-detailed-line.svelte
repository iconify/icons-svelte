<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9xz5fzpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9xz5fzpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mic-detailed-line" {...props}></Icon>
