<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxd-8e_9n.css';
import '../../css/t/tlplblg9a.css';
import '../../css/h/hse9jrbcs.css';
import '../../css/u/ucf26ob4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxd-8e_9n"/><path class="tlplblg9a"/><path clip-rule="evenodd" class="hse9jrbcs"/><path class="ucf26ob4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-alt" {...props}></Icon>
