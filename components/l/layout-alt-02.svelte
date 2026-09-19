<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1zjdybnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1zjdybnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layout-alt-02" {...props}></Icon>
