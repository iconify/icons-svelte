<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3n_6vj_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3n_6vj_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tumblr-filled" {...props}></Icon>
