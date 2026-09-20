<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf8m65tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myf8m65tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-open-fill" {...props}></Icon>
