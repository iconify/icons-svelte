<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqs0eobgx.css';
import '../../css/e/ejw3spdse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sqs0eobgx"/><path class="ejw3spdse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-left-20" {...props}></Icon>
