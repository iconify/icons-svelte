<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_qs-ppqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_qs-ppqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-right-solid" {...props}></Icon>
