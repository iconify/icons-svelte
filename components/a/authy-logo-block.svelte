<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojt3_9lvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojt3_9lvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:authy-logo-block" {...props}></Icon>
