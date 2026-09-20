<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltktxhbob.css';
import '../../css/j/j6gfa_94f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltktxhbob"/><path class="j6gfa_94f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:reply" {...props}></Icon>
