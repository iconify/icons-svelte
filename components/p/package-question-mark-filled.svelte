<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldqp-hbll.css';
import '../../css/g/ghz_-ebeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldqp-hbll"/><path class="ghz_-ebeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-question-mark-filled" {...props}></Icon>
