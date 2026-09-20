<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1l0m8bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1l0m8bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-2" {...props}></Icon>
