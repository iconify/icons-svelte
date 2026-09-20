<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs47fsy6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs47fsy6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:magic-wand" {...props}></Icon>
