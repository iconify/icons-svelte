<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ebrqn7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2ebrqn7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:circle-triangle-right-fill" {...props}></Icon>
