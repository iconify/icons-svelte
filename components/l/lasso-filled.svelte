<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egbfch_mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egbfch_mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lasso-filled" {...props}></Icon>
