<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmmio3p-i.css';
import '../../css/w/w7niv3b6v.css';
import '../../css/c/c76r55w5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmmio3p-i"/><path class="w7niv3b6v"/><path class="c76r55w5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:bug-duotone" {...props}></Icon>
