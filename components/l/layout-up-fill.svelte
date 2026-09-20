<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncm8dqb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncm8dqb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:layout-up-fill" {...props}></Icon>
