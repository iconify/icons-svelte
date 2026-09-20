<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjnvnmevq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjnvnmevq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:icq-logo-1-block" {...props}></Icon>
