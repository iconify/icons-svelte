<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l22617b1g.css';
import '../../css/o/obtf6y2yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l22617b1g"/><path class="obtf6y2yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:book-open-outline" {...props}></Icon>
