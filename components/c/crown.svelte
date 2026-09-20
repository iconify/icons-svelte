<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7vnvrupw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7vnvrupw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crown" {...props}></Icon>
