<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ucobmfu.css';
import '../../css/z/z6ggt6ojm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2ucobmfu"/><path class="z6ggt6ojm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pack" {...props}></Icon>
