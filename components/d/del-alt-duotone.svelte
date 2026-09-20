<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kazka8b2e.css';
import '../../css/b/b0insabyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="kazka8b2e"/><path clip-rule="evenodd" class="b0insabyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:del-alt-duotone" {...props}></Icon>
