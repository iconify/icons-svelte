<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hafoy85cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hafoy85cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-l-box-outline" {...props}></Icon>
