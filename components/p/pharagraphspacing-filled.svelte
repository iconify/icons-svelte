<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqpby_sqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqpby_sqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pharagraphspacing-filled" {...props}></Icon>
