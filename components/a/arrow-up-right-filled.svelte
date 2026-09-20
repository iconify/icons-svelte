<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6kgg4c6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6kgg4c6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-up-right-filled" {...props}></Icon>
