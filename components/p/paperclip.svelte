<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j27j2c08b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j27j2c08b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:paperclip" {...props}></Icon>
