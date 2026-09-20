<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugfsqiunw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugfsqiunw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-left-plus" {...props}></Icon>
