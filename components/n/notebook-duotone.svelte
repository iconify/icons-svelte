<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lczir7byp.css';
import '../../css/u/umplx46gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lczir7byp"/><path class="umplx46gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:notebook-duotone" {...props}></Icon>
