<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5wfopi9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5wfopi9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:credit-card-thin" {...props}></Icon>
