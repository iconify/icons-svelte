<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv55i0bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv55i0bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-types-remix" {...props}></Icon>
