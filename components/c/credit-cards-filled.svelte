<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm6q69bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm6q69bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-cards-filled" {...props}></Icon>
