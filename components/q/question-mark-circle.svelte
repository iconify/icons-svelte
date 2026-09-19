<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2iac9bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g2iac9bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:question-mark-circle" {...props}></Icon>
