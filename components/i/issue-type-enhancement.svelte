<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3bjr7btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k3bjr7btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-enhancement" {...props}></Icon>
