<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiexm0b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oiexm0b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:credit-card-detailed-fill" {...props}></Icon>
