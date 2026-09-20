<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny74hhq-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny74hhq-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pika" {...props}></Icon>
