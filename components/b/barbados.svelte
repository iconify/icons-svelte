<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip1kq0bvs.css';
import '../../css/n/nu-yx8b6b.css';
import '../../css/a/awv06sg9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ip1kq0bvs"/><path class="nu-yx8b6b"/><path class="awv06sg9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:barbados" {...props}></Icon>
