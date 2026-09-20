<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe3mpopda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe3mpopda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:archive-sharp" {...props}></Icon>
