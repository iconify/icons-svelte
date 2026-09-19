<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7s-6cbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7s-6cbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-wizard-hat-filled" {...props}></Icon>
