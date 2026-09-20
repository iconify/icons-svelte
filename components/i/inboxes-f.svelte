<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eno-67mfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="eno-67mfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:inboxes-f" {...props}></Icon>
