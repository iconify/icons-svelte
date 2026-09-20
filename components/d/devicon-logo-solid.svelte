<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsrl8zu3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gsrl8zu3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:devicon-logo-solid" {...props}></Icon>
