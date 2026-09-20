<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teryzmwzf.css';
import '../../css/f/f1vawn50g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teryzmwzf"/><path class="f1vawn50g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:notes-upload-bold" {...props}></Icon>
