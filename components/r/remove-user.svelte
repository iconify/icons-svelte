<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tctwulbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tctwulbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:remove-user" {...props}></Icon>
