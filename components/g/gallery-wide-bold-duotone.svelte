<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf2z5ab9j.css';
import '../../css/i/iubpiibgw.css';
import '../../css/c/cnfam5b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2z5ab9j"/><path clip-rule="evenodd" class="iubpiibgw"/><path class="cnfam5b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-wide-bold-duotone" {...props}></Icon>
