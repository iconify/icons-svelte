<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6agol35u.css';
import '../../css/p/pd8yij20i.css';
import '../../css/e/e70d0jzgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6agol35u"/><path class="pd8yij20i"/><path clip-rule="evenodd" class="e70d0jzgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-top-left-bold" {...props}></Icon>
