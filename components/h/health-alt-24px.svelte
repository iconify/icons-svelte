<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfx6z8-hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfx6z8-hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-alt-24px" {...props}></Icon>
