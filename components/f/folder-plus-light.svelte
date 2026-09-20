<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14-lebxp.css';
import '../../css/j/j84ijjsgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m14-lebxp"/><path clip-rule="evenodd" class="j84ijjsgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-plus-light" {...props}></Icon>
