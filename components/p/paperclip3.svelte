<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grlu2bcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grlu2bcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip3" {...props}></Icon>
