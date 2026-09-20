<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr1ubj--e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qr1ubj--e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-key-result" {...props}></Icon>
