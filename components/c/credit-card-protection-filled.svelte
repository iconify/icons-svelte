<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-ak_b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq-ak_b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-protection-filled" {...props}></Icon>
