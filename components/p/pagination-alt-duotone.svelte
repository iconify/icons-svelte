<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnacpw3wj.css';
import '../../css/n/n4kggwbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnacpw3wj"/><rect class="n4kggwbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pagination-alt-duotone" {...props}></Icon>
