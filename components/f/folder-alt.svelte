<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veiu-2wux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="veiu-2wux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-alt" {...props}></Icon>
